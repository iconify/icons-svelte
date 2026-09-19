<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw0ytwqdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yw0ytwqdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni5f3a-box-filled" {...props}></Icon>
