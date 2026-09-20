<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt39gtb6i.css';
import '../../css/f/fk2bifb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt39gtb6i"/><path class="fk2bifb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signin-alt" {...props}></Icon>
