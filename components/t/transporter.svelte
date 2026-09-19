<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/r9v9olbvu.css';
import '../../css/q/qfqew4w1l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5viI2z1N"><g class="v3_i3wktz"><path class="r9v9olbvu"/><path class="qfqew4w1l"/></g></mask></defs><path mask="url(#SVG5viI2z1N)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:transporter" {...props}></Icon>
