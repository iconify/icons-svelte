<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s795qebot.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i3nt_5b5j.css';
import '../../css/c/c5gfowu_b.css';
import '../../css/m/mgsxq4bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s795qebot secondary"/><g class="dt0cm9dhy primary"><path class="i3nt_5b5j"/><path class="c5gfowu_b"/><path class="mgsxq4bxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:users-duo" {...props}></Icon>
