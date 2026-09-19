<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/v/vz-dvwm5z.css';
import '../../css/q/q4ik7kbpj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGz8FQVdSf"><g class="v3_i3wktz"><path class="vz-dvwm5z"/><path class="q4ik7kbpj"/></g></mask></defs><path mask="url(#SVGz8FQVdSf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tree-list" {...props}></Icon>
