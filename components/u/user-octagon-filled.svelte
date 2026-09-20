<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/texuw4bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="texuw4bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-octagon-filled" {...props}></Icon>
