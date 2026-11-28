<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sbm9b5tlm.css';
import '../../css/k/k7ctk0cpn.css';
import '../../css/i/i5obohb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sbm9b5tlm"/><path class="k7ctk0cpn"/><path class="i5obohb9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:whistle" {...props}></Icon>
