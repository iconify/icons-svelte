<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srui7osvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="srui7osvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:up-circle-solid" {...props}></Icon>
