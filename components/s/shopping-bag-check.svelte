<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jg3y9yc8q.css';
import '../../css/k/kmvaoyg2v.css';
import '../../css/z/z05-hg-by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jg3y9yc8q"/><path class="kmvaoyg2v"/><path class="z05-hg-by"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shopping-bag-check" {...props}></Icon>
