<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh0unhbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jh0unhbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:website-alt" {...props}></Icon>
