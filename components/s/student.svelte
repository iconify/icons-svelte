<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ndrqb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="x3ndrqb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:student" {...props}></Icon>
