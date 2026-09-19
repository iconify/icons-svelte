<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf_6axbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf_6axbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shield-yes-fill" {...props}></Icon>
