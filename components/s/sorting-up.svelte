<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl4b96bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4b96bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-up" {...props}></Icon>
