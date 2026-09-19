<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/horpi928m.css';
import '../../css/f/fwlwgzfat.css';
import '../../css/u/udpwpkf8i.css';
import '../../css/h/hq4svlbqs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGw1dXGdOO"><g class="ft5dv1b6b"><path class="horpi928m"/><path class="fwlwgzfat"/><path class="udpwpkf8i"/><path class="hq4svlbqs"/></g></mask></defs><path mask="url(#SVGw1dXGdOO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:target-one" {...props}></Icon>
