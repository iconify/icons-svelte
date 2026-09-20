<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti3zyb3xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti3zyb3xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-outline" {...props}></Icon>
