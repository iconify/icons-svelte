<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/tlurdrb3p.css';
import '../../css/e/etpgz9bon.css';
import '../../css/v/vm6pr9bdj.css';
import '../../css/o/od6e1z5th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="tlurdrb3p wm-shadow"/><path class="etpgz9bon wm-shadow"/><path class="vm6pr9bdj"/><path class="od6e1z5th"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:skull" {...props}></Icon>
