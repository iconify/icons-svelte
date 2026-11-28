<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz_qnk-ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1786,"height":428,"left":107,"top":786};
const content = `<path class="kz_qnk-ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tata-consultancy-services-light" {...props}></Icon>
