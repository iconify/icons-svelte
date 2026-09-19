<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/o/o2671ob9n.css';
import '../../css/q/quu14abrb.css';
import '../../css/f/f-jvjmbhp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaOCHLcoJ"><g class="s9cl3zbei"><path class="oo_vs07_g"/><path class="o2671ob9n"/><path class="quu14abrb"/><path class="f-jvjmbhp"/></g></mask></defs><path mask="url(#SVGaOCHLcoJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:volkswagen" {...props}></Icon>
