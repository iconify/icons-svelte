<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/e2w5edbxq.css';
import '../../css/t/tyi7s5b9y.css';
import '../../css/b/bydi6pbak.css';
import '../../css/i/it3lebcor.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqzZYu2uI"><g class="s9cl3zbei"><path class="e2w5edbxq"/><path class="tyi7s5b9y"/><path class="bydi6pbak"/><path class="it3lebcor"/></g></mask></defs><path mask="url(#SVGqzZYu2uI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shaver" {...props}></Icon>
