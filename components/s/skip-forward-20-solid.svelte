<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl9a3_bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fl9a3_bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:skip-forward-20-solid" {...props}></Icon>
