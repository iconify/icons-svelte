<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aojytvq1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aojytvq1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-horizontal-fill" {...props}></Icon>
