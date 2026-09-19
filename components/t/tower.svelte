<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/mpz_0zach.css';
import '../../css/j/j9hg1or3h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYDbtOuNw"><g class="v3_i3wktz"><path class="mpz_0zach"/><path class="j9hg1or3h"/></g></mask></defs><path mask="url(#SVGYDbtOuNw)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tower" {...props}></Icon>
