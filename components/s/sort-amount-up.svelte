<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr_ntm2dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr_ntm2dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sort-amount-up" {...props}></Icon>
