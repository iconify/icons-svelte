<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbolm7bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mbolm7bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vue-js-dark" {...props}></Icon>
