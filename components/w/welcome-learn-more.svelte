<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iapr2gepq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iapr2gepq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:welcome-learn-more" {...props}></Icon>
