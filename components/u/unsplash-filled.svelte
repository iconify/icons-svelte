<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oci2gci4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oci2gci4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:unsplash-filled" {...props}></Icon>
