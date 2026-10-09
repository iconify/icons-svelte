<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szva8fs1o.css';
import '../../css/f/fgpw0_ztz.css';
import '../../css/n/n75s5g__s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="szva8fs1o"/><path class="fgpw0_ztz"/><path class="n75s5g__s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sleet-20" {...props}></Icon>
