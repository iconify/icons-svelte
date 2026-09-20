<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj_no0yup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pj_no0yup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:western-digital-light" {...props}></Icon>
