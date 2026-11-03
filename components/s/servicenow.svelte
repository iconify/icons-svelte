<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s90m0hzje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s90m0hzje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:servicenow" {...props}></Icon>
