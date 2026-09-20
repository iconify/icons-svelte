<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvwv9fbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwv9fbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:shield-plus" {...props}></Icon>
