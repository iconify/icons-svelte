<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3ux1061w.css';
import '../../css/d/dyii5ab_p.css';
import '../../css/k/kvy4ghbal.css';
import '../../css/e/eqh2q3bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n3ux1061w"/><path class="dyii5ab_p"/><path class="kvy4ghbal"/><path class="eqh2q3bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-meter-20" {...props}></Icon>
