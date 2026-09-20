<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpd_00bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpd_00bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-left-down-outline" {...props}></Icon>
