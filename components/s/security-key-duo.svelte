<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smirgkmzn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pbji87ens.css';
import '../../css/x/x20ovybwp.css';
import '../../css/u/ueob06b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary smirgkmzn"/><g class="dt0cm9dhy primary"><path class="pbji87ens"/><path class="x20ovybwp"/><path class="ueob06b-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:security-key-duo" {...props}></Icon>
