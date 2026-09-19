<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol2-_5b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol2-_5b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:twitter" {...props}></Icon>
