<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/f69ughbml.css';
import '../../css/r/r1mdubbli.css';
import '../../css/h/h79q5vbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="f69ughbml"/><circle class="r1mdubbli"/><path class="h79q5vbot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:warehousing" {...props}></Icon>
