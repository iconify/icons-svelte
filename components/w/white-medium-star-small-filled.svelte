<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4gp4vbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="s4gp4vbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-medium-star-small-filled" {...props}></Icon>
