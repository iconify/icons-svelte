<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig7v8bb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ig7v8bb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sentry" {...props}></Icon>
