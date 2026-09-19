<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkh8abbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="tkh8abbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-headset-26" {...props}></Icon>
