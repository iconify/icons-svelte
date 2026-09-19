<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/i/iyn5nib5u.css';
import '../../css/x/xrwtinblr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3UgbJdrl"><g class="wwvp95byt"><rect class="iyn5nib5u"/><path class="xrwtinblr"/></g></mask></defs><path mask="url(#SVG3UgbJdrl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:table" {...props}></Icon>
