<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/a/aq9_ukftn.css';
import '../../css/f/fz8efub8i.css';
import '../../css/b/bd9gczbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG5de1ubJX"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="aq9_ukftn"/><path class="fz8efub8i"/></g></mask></defs><circle mask="url(#SVG5de1ubJX)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:water-drop-circle-filled" {...props}></Icon>
