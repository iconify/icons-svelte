<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lfwn9qb7o.css';
import '../../css/o/o0l6usxvj.css';
import '../../css/g/ghf43lb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="lfwn9qb7o"/><path clip-rule="evenodd" class="o0l6usxvj"/><path class="ghf43lb4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-add" {...props}></Icon>
