<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otxbt5c7t.css';
import '../../css/k/k7-izcbee.css';
import '../../css/e/e_r9uibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otxbt5c7t"/><path class="k7-izcbee"/><path class="e_r9uibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-check-filled" {...props}></Icon>
