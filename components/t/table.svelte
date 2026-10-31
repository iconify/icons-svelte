<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/q/q8i6dbbuh.css';
import '../../css/b/bdjqbm-ub.css';
import '../../css/c/caum75byk.css';
import '../../css/g/g07d2nb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="q8i6dbbuh wm-shadow"/><path class="bdjqbm-ub wm-shadow"/><path class="caum75byk"/><path class="g07d2nb5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:table" {...props}></Icon>
