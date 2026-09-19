<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s503_9beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="s503_9beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-github" {...props}></Icon>
