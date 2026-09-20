<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo_dqemwo.css';
import '../../css/r/r-kz3ibtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo_dqemwo"/><path class="r-kz3ibtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-box-duotone" {...props}></Icon>
