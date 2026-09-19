<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygdmzg_ll.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQleDNc7g"><path clip-rule="evenodd" class="ygdmzg_ll"/></mask></defs><path mask="url(#SVGQleDNc7g)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:triangle" {...props}></Icon>
