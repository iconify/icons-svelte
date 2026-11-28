<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7up-acjy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/te-6n-baq.css';
import '../../css/z/zb9fuvb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary v7up-acjy"/><g class="dt0cm9dhy primary"><path class="te-6n-baq"/><path class="zb9fuvb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tablet-duo" {...props}></Icon>
