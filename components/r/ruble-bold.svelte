<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcuss6sft.css';
import '../../css/a/arfojkbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcuss6sft"/><path clip-rule="evenodd" class="arfojkbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruble-bold" {...props}></Icon>
