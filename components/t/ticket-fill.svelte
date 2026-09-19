<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzeohi03u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzeohi03u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:ticket-fill" {...props}></Icon>
