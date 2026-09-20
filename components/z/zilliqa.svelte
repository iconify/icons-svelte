<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz15zbcnl.css';
import '../../css/n/ngd8w9bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz15zbcnl"/><path class="ngd8w9bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zilliqa" {...props}></Icon>
