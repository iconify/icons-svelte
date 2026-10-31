<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gup0_nber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gup0_nber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-20-solid" {...props}></Icon>
