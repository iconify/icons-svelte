<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz4c4xbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sz4c4xbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-circle" {...props}></Icon>
