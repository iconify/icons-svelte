<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/s/s1brhjmbn.css';
import '../../css/j/j66rvjbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGlgxcXbAS" class="n1mjunbsu"><path clip-rule="evenodd" class="s1brhjmbn"/></mask><path clip-rule="evenodd" mask="url(#SVGlgxcXbAS)" class="j66rvjbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:whatsapp-solid" {...props}></Icon>
