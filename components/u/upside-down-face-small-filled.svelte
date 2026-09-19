<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pocbklbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pocbklbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:upside-down-face-small-filled" {...props}></Icon>
