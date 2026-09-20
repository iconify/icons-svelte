<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz32jjbma.css';
import '../../css/m/mg-i62fru.css';
import '../../css/r/rzyax-b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz32jjbma"/><path class="mg-i62fru"/><path class="rzyax-b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:web-section" {...props}></Icon>
