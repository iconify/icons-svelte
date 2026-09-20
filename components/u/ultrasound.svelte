<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b84ui104o.css';
import '../../css/w/wcbu4acoh.css';
import '../../css/y/y--cdmb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="b84ui104o"/><path class="wcbu4acoh"/><path class="y--cdmb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:ultrasound" {...props}></Icon>
