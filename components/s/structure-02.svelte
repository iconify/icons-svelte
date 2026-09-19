<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jsk1cskcf.css';
import '../../css/s/spnb3cbwy.css';
import '../../css/k/kpvc2fb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jsk1cskcf"/><path class="spnb3cbwy"/><path class="kpvc2fb7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:structure-02" {...props}></Icon>
