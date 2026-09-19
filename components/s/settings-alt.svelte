<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0ge21b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0ge21b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:settings-alt" {...props}></Icon>
