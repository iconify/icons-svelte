<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s264hrbbe.css';
import '../../css/m/m5n_ehoon.css';
import '../../css/k/kemfy5bie.css';
import '../../css/d/d9s5sfbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s264hrbbe"/><path class="m5n_ehoon"/><path clip-rule="evenodd" class="kemfy5bie"/><path class="d9s5sfbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-results" {...props}></Icon>
