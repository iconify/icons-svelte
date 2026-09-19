<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nkqj6j90v.css';
import '../../css/h/hlsy3c2kt.css';
import '../../css/g/gyevrrb6e.css';
import '../../css/z/z2na20gje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nkqj6j90v"/><path class="hlsy3c2kt"/><circle class="gyevrrb6e"/><circle class="z2na20gje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:school-bell-01" {...props}></Icon>
