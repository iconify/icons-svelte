<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b53cjslek.css';
import '../../css/k/k_gbamc1v.css';
import '../../css/h/hi8bol3jn.css';
import '../../css/f/fk81ubbzb.css';
import '../../css/u/ucpl_kbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b53cjslek"/><path class="k_gbamc1v"/><path class="hi8bol3jn"/><path class="fk81ubbzb"/><path class="ucpl_kbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-square-2-outline" {...props}></Icon>
