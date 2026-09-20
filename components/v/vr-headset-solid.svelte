<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1qap0bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="g1qap0bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:vr-headset-solid" {...props}></Icon>
