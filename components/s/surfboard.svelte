<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o612d83qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o612d83qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:surfboard" {...props}></Icon>
