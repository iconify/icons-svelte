<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/k/k87xdfbfj.css';
import '../../css/v/v8g1xozen.css';
import '../../css/w/w4vhh3s5s.css';
import '../../css/e/etmqncjox.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcWmdtcgB"><g class="s9cl3zbei"><rect class="k87xdfbfj"/><path class="v8g1xozen"/><path class="w4vhh3s5s"/><path class="etmqncjox"/></g></mask></defs><path mask="url(#SVGcWmdtcgB)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:transport" {...props}></Icon>
