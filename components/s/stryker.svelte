<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcwz-8byp.css';
import '../../css/j/jz_z96ofw.css';
import '../../css/h/hx1pgx08q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="wcwz-8byp"><path class="jz_z96ofw"/><path class="hx1pgx08q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:stryker" {...props}></Icon>
