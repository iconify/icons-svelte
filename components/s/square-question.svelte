<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-c1bbea.css';
import '../../css/z/zrkdwxohg.css';
import '../../css/r/rij442pdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc-c1bbea"/><circle class="zrkdwxohg"/><path class="rij442pdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-question" {...props}></Icon>
