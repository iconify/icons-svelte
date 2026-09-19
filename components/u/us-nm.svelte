<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/r/r-ww-8qki.css';
import '../../css/m/m8wx0nbbz.css';
import '../../css/m/moij-qjjo.css';
import '../../css/i/ibv5i6bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="r-ww-8qki"/><path class="m8wx0nbbz"/><circle class="moij-qjjo"/><circle class="ibv5i6bxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:us-nm" {...props}></Icon>
