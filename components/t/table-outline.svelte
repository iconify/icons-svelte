<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yla9h-91z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yla9h-91z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-outline" {...props}></Icon>
