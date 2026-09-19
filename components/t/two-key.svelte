<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/g/gvf5nybvn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjQ74kZVQ"><g class="wwvp95byt"><rect class="g47cb4b4t"/><path class="gvf5nybvn"/></g></mask></defs><path mask="url(#SVGjQ74kZVQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:two-key" {...props}></Icon>
