<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfqc5hbns.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPo9Qqccj"><path class="nfqc5hbns"/></mask></defs><path mask="url(#SVGPo9Qqccj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:vest" {...props}></Icon>
