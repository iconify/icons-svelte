<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd4k-hpkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qd4k-hpkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:xubuntu" {...props}></Icon>
