<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oum_zll5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oum_zll5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:taxiing-line" {...props}></Icon>
