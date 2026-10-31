<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbpqh67iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbpqh67iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:view-split" {...props}></Icon>
