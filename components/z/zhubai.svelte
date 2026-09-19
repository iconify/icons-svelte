<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ayi0ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e_ayi0ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:zhubai" {...props}></Icon>
