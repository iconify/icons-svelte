<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/sjxgbg2th.css';
import '../../css/t/tf3n6m1cy.css';
import '../../css/l/ljhemfwhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="sjxgbg2th wm-shadow"/><path class="tf3n6m1cy wm-shadow"/><path class="ljhemfwhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:signal" {...props}></Icon>
