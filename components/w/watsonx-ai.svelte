<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6vzv4bqp.css';
import '../../css/s/s3ckdxwss.css';
import '../../css/v/vbagb8yxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v6vzv4bqp"/><path class="s3ckdxwss"/><path class="vbagb8yxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:watsonx-ai" {...props}></Icon>
