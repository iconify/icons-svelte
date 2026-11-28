<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6wedk6gg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b4a62x58a.css';
import '../../css/h/h1zbsh5sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z6wedk6gg"/><g class="dt0cm9dhy primary"><path class="b4a62x58a"/><path class="h1zbsh5sl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sun-dim-duo" {...props}></Icon>
