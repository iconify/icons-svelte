<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z6gc64byl.css';
import '../../css/a/afkv757cy.css';
import '../../css/x/xhhh0v1_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="z6gc64byl"/><path class="afkv757cy"/><path class="xhhh0v1_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:safety-danger-mudslide" {...props}></Icon>
