<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyfb9dbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fyfb9dbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-medium-star-small" {...props}></Icon>
