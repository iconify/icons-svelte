<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3jh1-bnt.css';
import '../../css/d/dblasrb2v.css';
import '../../css/w/wxc7mbbhr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTk2kDbTG"><g class="q3jh1-bnt"><path class="dblasrb2v"/><path class="wxc7mbbhr"/></g></mask></defs><path mask="url(#SVGTk2kDbTG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:youtube" {...props}></Icon>
