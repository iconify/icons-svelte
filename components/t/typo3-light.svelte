<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-bo3ibyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v-bo3ibyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typo3-light" {...props}></Icon>
