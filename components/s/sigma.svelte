<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftehj-c2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ftehj-c2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:sigma" {...props}></Icon>
