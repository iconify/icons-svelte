<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyc7oevht.css';
import '../../css/a/abs0vhb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyc7oevht"/><path clip-rule="evenodd" class="abs0vhb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-2-outline" {...props}></Icon>
