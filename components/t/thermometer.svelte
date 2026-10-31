<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/fnfctw6un.css';
import '../../css/u/uugk94daf.css';
import '../../css/q/q90ibrbvw.css';
import '../../css/w/wa_l-6bwp.css';
import '../../css/g/g1j1je9rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="fnfctw6un wm-shadow"/><path class="uugk94daf wm-shadow"/><path class="q90ibrbvw"/><path class="wa_l-6bwp"/><path class="g1j1je9rj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:thermometer" {...props}></Icon>
