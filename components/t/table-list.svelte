<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3tvasb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3tvasb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-list" {...props}></Icon>
