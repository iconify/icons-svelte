<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbk-ufbag.css';
import '../../css/s/syww2wg1x.css';
import '../../css/h/h3qo2x5ah.css';
import '../../css/t/t5hz4nbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rbk-ufbag"/><path class="syww2wg1x"/><path class="h3qo2x5ah"/><path class="t5hz4nbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:supercapacitor-20" {...props}></Icon>
