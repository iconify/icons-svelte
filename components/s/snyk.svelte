<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iowhspbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":512};
const content = `<path class="iowhspbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:snyk" {...props}></Icon>
