<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtu6puqov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="dtu6puqov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:theta" {...props}></Icon>
