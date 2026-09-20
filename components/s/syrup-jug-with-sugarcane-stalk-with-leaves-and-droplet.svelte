<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guokccb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="guokccb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:syrup-jug-with-sugarcane-stalk-with-leaves-and-droplet" {...props}></Icon>
