<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0cyhdctz.css';
import '../../css/n/nda3cdcdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0cyhdctz"/><path clip-rule="evenodd" class="nda3cdcdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-vacuum-cleaner-2-bold" {...props}></Icon>
