<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmgp09f-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hmgp09f-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rust" {...props}></Icon>
