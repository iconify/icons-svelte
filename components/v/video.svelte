<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr5gkzbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fr5gkzbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:video" {...props}></Icon>
