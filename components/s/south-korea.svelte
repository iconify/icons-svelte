<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7x5h9bzy.css';
import '../../css/l/lpmxo1cba.css';
import '../../css/o/ok1s67w0q.css';
import '../../css/u/uga0ovbvj.css';
import '../../css/s/snp287xku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7x5h9bzy"/><path class="lpmxo1cba"/><path class="ok1s67w0q"/><path class="uga0ovbvj"/><path class="snp287xku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:south-korea" {...props}></Icon>
