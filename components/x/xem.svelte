<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiaxrbbmg.css';
import '../../css/f/fit1ekbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiaxrbbmg"/><path class="fit1ekbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xem" {...props}></Icon>
