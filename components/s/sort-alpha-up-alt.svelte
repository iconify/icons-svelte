<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us7pqh5os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="us7pqh5os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-alpha-up-alt" {...props}></Icon>
