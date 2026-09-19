<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b13as3l5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b13as3l5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:text-color" {...props}></Icon>
