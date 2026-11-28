<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk0_bffgj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b8ykfyb9e.css';
import '../../css/w/w9yqwqbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk0_bffgj secondary"/><g class="dt0cm9dhy primary"><path class="b8ykfyb9e"/><path class="w9yqwqbyt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tag-duo" {...props}></Icon>
