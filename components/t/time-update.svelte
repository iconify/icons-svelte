<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg_zdh7-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cg_zdh7-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:time-update" {...props}></Icon>
