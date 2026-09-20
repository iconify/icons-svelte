<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odal1gbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odal1gbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:visualstudiocode" {...props}></Icon>
