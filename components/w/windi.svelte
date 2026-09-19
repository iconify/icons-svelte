<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkvh3ejfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":512};
const content = `<path class="lkvh3ejfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:windi" {...props}></Icon>
