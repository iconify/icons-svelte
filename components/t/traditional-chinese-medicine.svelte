<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/h/hrcmblb0d.css';
import '../../css/q/qshv2gqkc.css';
import '../../css/k/kewv3zbqz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG42lgieqI"><g class="s9cl3zbei"><path clip-rule="evenodd" class="hrcmblb0d"/><path class="qshv2gqkc"/><path class="kewv3zbqz"/></g></mask></defs><path mask="url(#SVG42lgieqI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:traditional-chinese-medicine" {...props}></Icon>
