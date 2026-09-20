<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0q_ccse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak0q_ccse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:verifywise-dark" {...props}></Icon>
