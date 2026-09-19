<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4cqdcc1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e4cqdcc1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:skype-with-circle" {...props}></Icon>
