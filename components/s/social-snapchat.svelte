<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_26yooza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="v_26yooza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-snapchat" {...props}></Icon>
