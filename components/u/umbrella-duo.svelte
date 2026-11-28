<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz-qoubxo.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fz90fnpjg.css';
import '../../css/q/qoxrnac0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz-qoubxo secondary"/><g class="dt0cm9dhy primary"><path class="fz90fnpjg"/><path class="qoxrnac0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:umbrella-duo" {...props}></Icon>
