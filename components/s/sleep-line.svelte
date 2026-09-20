<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osg8puemb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osg8puemb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sleep-line" {...props}></Icon>
