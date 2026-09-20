<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/ergq9t7hr.css';
import '../../css/o/odx7w3bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ergq9t7hr"/><path class="odx7w3bem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:telegram-light" {...props}></Icon>
