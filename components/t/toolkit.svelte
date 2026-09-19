<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/ehq94ab3m.css';
import '../../css/e/ewapn8bvm.css';
import '../../css/u/uanaekbsb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKmZ2HFof"><g class="v3_i3wktz"><path class="ehq94ab3m"/><path class="ewapn8bvm"/><path class="uanaekbsb"/></g></mask></defs><path mask="url(#SVGKmZ2HFof)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:toolkit" {...props}></Icon>
