<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f778dovca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f778dovca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:shield-exclamation" {...props}></Icon>
