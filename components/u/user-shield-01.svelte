<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/byr5dkqie.css';
import '../../css/b/bbpve-yut.css';
import '../../css/q/qjechsbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byr5dkqie"/><circle class="bbpve-yut"/><path class="qjechsbnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-shield-01" {...props}></Icon>
